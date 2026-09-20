<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv1tmnbqm.css';
import '../../css/p/p_f0lhbyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yv1tmnbqm"/><path clip-rule="evenodd" class="p_f0lhbyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:basic-ui-add-user" /></template>
