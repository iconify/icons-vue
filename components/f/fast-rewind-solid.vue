<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ljr-rm75o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ljr-rm75o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:fast-rewind-solid" /></template>
