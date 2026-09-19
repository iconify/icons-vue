<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pbrk_2byt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbrk_2byt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:indicator" /></template>
