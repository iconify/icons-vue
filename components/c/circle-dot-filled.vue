<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fpuxyac7l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fpuxyac7l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dot-filled" /></template>
