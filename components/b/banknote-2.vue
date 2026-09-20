<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eras3s65f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eras3s65f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:banknote-2" /></template>
