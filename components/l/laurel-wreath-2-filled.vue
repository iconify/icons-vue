<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd00kcbld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bd00kcbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:laurel-wreath-2-filled" /></template>
