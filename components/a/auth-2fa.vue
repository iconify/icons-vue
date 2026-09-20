<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j0ac79yru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0ac79yru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:auth-2fa" /></template>
