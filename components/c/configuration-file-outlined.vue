<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4tgbvbns.css';
import '../../css/o/o7g2p2-br.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4tgbvbns"/><path class="o7g2p2-br"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:configuration-file-outlined" /></template>
