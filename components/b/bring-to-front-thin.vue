<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alf14997c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="alf14997c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pullo:bring-to-front-thin" /></template>
