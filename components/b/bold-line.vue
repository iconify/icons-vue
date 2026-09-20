<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnc9n5bok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnc9n5bok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:bold-line" /></template>
