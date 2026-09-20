<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5ld3lc5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o5ld3lc5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:hammer-fill" /></template>
