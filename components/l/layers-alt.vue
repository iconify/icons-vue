<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jh21ckg-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jh21ckg-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:layers-alt" /></template>
