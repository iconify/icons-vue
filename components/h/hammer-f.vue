<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sztxhqb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-1.5,"top":-1.5};
const content = `<path class="sztxhqb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:hammer-f" /></template>
