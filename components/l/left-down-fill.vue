<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mvvw2084a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mvvw2084a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:left-down-fill" /></template>
