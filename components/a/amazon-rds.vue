<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axkw0ac2k.css';
import '../../css/a/aytd6oskt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="axkw0ac2k"/><path class="aytd6oskt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:amazon-rds" /></template>
