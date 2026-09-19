<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a5w600x0k.css';
import '../../css/p/pl69o0bph.css';
import '../../css/b/bemq7eb7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="a5w600x0k"/><circle class="pl69o0bph"/><circle class="bemq7eb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ellipsis-vertical-outline" /></template>
