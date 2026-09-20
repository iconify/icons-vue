<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-qn9i21d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-qn9i21d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:bolt-filled" /></template>
