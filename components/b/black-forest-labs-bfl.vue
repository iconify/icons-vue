<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8goj0b8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b8goj0b8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:black-forest-labs-bfl" /></template>
