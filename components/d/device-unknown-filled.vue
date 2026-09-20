<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/brqcmhv-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="brqcmhv-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-unknown-filled" /></template>
