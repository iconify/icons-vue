<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zebv5wb6t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zebv5wb6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:flag-filled" /></template>
