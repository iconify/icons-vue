<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pjg5rdbcc.css';
import '../../css/b/bgc6dhdml.css';
import '../../css/n/nbcjn_bcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pjg5rdbcc"/><path class="bgc6dhdml"/><path class="nbcjn_bcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:belt-drive-20" /></template>
