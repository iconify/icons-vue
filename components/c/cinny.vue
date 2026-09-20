<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w87a21b3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w87a21b3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:cinny" /></template>
