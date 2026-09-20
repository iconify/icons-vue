<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5ra11bdp.css';
import '../../css/l/lb-bssbki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w5ra11bdp"/><path class="lb-bssbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:checkbox-24" /></template>
