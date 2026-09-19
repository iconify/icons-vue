<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_60j9k2m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_60j9k2m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:directions-02" /></template>
