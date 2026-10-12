<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yynfaacui.css';
import '../../css/t/tbe9gjgli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yynfaacui"/><path class="tbe9gjgli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:emoji-neutral-stroke-20" /></template>
