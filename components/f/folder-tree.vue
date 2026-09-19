<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q62ov693u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q62ov693u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:folder-tree" /></template>
