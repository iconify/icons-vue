<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b_hnyxb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b_hnyxb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:c-sharp" /></template>
