<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b4p62tssf.css';
import '../../css/h/hvsefo_2t.css';
import '../../css/q/qo_dlfbns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4p62tssf"/><path class="hvsefo_2t"/><path class="qo_dlfbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:8-ball" /></template>
