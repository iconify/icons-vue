<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7s5tybmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7s5tybmk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-compare-arrows-sharp" /></template>
