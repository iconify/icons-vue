<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbkwyfbyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dbkwyfbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:angle-up-solid" /></template>
