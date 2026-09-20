<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/w/wbygb0tnm.css';
import '../../css/l/ly0q5ab1k.css';
import '../../css/e/ecmm5nb_w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="wbygb0tnm"/><path class="ly0q5ab1k"/><path class="ecmm5nb_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:crypto-close-up-group-chat-users-conversation" /></template>
