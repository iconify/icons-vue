<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-lvl5b7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-lvl5b7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:dice-one" /></template>
