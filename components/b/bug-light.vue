<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ugrz9ubjf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ugrz9ubjf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:bug-light" /></template>
