<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqz1aw1rt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqz1aw1rt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:flag-finish-light" /></template>
