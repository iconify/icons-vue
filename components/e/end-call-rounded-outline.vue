<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9vdnhbpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u9vdnhbpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:end-call-rounded-outline" /></template>
