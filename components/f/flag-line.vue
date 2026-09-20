<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdzajkb9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdzajkb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:flag-line" /></template>
