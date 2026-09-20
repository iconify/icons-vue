<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am0io7bqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="am0io7bqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:browse-off" /></template>
