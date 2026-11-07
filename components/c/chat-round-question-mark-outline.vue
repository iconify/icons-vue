<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qsm1dmd4a.css';
import '../../css/f/fnzdhr9jf.css';
import '../../css/x/x9024bb4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qsm1dmd4a"/><path class="fnzdhr9jf"/><path clip-rule="evenodd" class="x9024bb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-question-mark-outline" /></template>
