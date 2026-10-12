<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wo0c38buo.css';
import '../../css/c/ciwabiowf.css';
import '../../css/d/diidstw8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wo0c38buo"/><path clip-rule="evenodd" class="ciwabiowf"/><path class="diidstw8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:galaxy-filled" /></template>
