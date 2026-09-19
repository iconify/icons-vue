<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgbdqpwkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":23,"height":24};
const content = `<path class="bgbdqpwkf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:deskpro" /></template>
