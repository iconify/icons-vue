<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3-a3w-3w.css';
import '../../css/l/lonxz_wlc.css';
import '../../css/k/kj18kdbau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="c3-a3w-3w"/><path class="lonxz_wlc"/><path class="kj18kdbau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:ivory-coast" /></template>
