<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo0whm7za.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-1};
const content = `<path class="jo0whm7za"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:birthday-cake" /></template>
