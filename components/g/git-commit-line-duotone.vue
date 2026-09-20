<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/k/k90m4o-1e.css';
import '../../css/d/dd3evbk6v.css';
import '../../css/s/sduv6uq4w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="k90m4o-1e"/><path class="dd3evbk6v"/><path class="sduv6uq4w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:git-commit-line-duotone" /></template>
