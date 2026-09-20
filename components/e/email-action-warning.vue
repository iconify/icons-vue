<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/q/qdz2abcdv.css';
import '../../css/b/b-9kcut0b.css';
import '../../css/q/qd1ytjbdv.css';
import '../../css/x/xvc7nd93m.css';
import '../../css/e/elexycc3c.css';
import '../../css/d/d22o4rbyg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="qdz2abcdv"/><path class="b-9kcut0b"/><path class="qd1ytjbdv"/><path class="xvc7nd93m"/><path class="elexycc3c"/><path class="d22o4rbyg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:email-action-warning" /></template>
