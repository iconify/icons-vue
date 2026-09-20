<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-wg9bz4o.css';
import '../../css/s/s1d8djbvs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-wg9bz4o"/><path clip-rule="evenodd" class="s1d8djbvs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:blessing-line" /></template>
