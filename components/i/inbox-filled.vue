<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8hbf0lfj.css';
import '../../css/b/bw5sq60eg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8hbf0lfj"/><path class="bw5sq60eg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:inbox-filled" /></template>
