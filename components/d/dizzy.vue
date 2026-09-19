<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8ws9tb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="n8ws9tb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:dizzy" /></template>
