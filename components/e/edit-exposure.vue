<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv6e5ubox.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kv6e5ubox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:edit-exposure" /></template>
