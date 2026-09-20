<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oum74s82r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oum74s82r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:eye-off" /></template>
