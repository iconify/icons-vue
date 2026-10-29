<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9nmfjvdw.css';
import '../../css/c/cj8t6iwqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9nmfjvdw wm-k"/><path class="cj8t6iwqx wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:captions" /></template>
