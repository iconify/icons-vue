<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o9jkhxbmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":23,"height":24};
const content = `<path class="o9jkhxbmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:angle-dobule-down" /></template>
