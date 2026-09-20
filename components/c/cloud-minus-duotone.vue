<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/ba8lvwbib.css';
import '../../css/f/fmuqr9b0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba8lvwbib"/><path class="fmuqr9b0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:cloud-minus-duotone" /></template>
