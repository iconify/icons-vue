<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qklwflbvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qklwflbvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:hermesseg-dark" /></template>
