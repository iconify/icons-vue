<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbwz4ccyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbwz4ccyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:arrow-right-duotone" /></template>
