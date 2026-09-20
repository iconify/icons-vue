<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bpyq45sbd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bpyq45sbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-check-sharp" /></template>
