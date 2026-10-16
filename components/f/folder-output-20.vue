<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwb0facpd.css';
import '../../css/x/x5goyhbiu.css';
import '../../css/t/tqvccub8k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xwb0facpd"/><path class="x5goyhbiu"/><path class="tqvccub8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-output-20" /></template>
