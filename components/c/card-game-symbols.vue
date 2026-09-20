<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/w/wsabpzbeh.css';
import '../../css/i/i18t-xexp.css';
import '../../css/u/uybhwbbak.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="wsabpzbeh"/><path class="i18t-xexp"/><path class="uybhwbbak"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand-color:card-game-symbols" /></template>
