<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xir71cb7c.css';
import '../../css/n/n6l7qezyb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xir71cb7c"/><path class="n6l7qezyb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-diff-24" /></template>
