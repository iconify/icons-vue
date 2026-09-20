<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chji1lpeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chji1lpeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:banknote-2-plus-sharp" /></template>
