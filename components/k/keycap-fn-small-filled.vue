<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kv6d8pzsj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="kv6d8pzsj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:keycap-fn-small-filled" /></template>
