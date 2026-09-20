<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bk6089bek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="bk6089bek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:conversation-filled" /></template>
