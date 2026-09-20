<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8ei05v9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8ei05v9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:kickstarter" /></template>
