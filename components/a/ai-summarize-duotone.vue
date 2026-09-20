<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfgdjs2-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfgdjs2-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:ai-summarize-duotone" /></template>
