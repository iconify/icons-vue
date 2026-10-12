<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4akmytgw.css';
import '../../css/y/yg7brjbpd.css';
import '../../css/n/nq41ynbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4akmytgw"/><path clip-rule="evenodd" class="yg7brjbpd"/><path class="nq41ynbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:file-cog-filled" /></template>
