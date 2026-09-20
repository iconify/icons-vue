<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7lj7fb9d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7lj7fb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:keepassxc" /></template>
