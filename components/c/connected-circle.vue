<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rbh3tpq0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rbh3tpq0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:connected-circle" /></template>
