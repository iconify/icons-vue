<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rgp1bebal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-1};
const content = `<path class="rgp1bebal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:birthday-cake-f" /></template>
