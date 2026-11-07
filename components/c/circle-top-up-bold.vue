<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejn_m3b5w.css';
import '../../css/x/x-i7oifjp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejn_m3b5w"/><path class="x-i7oifjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:circle-top-up-bold" /></template>
