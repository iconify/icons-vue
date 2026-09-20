<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc8ang44w.css';
import '../../css/e/eh-2z7b3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="pc8ang44w"/><path class="eh-2z7b3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:duo-agentic-chat" /></template>
