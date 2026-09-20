<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/z/za-y-u5-e.css';
import '../../css/p/pruluhbfg.css';
import '../../css/q/qhu_wpbju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="za-y-u5-e"/><path class="pruluhbfg"/><path class="qhu_wpbju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:currency-dollar-euro-chat-bubble" /></template>
