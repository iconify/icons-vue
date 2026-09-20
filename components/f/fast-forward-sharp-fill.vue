<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p9s4n-b7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p9s4n-b7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:fast-forward-sharp-fill" /></template>
