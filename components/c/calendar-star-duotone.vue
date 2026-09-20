<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmunasb2f.css';
import '../../css/x/xtpeb-edw.css';
import '../../css/m/mnr4ubw3e.css';
import '../../css/f/fzydk7e5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmunasb2f"/><g class="xtpeb-edw"><path clip-rule="evenodd" class="mnr4ubw3e"/><path class="fzydk7e5i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:calendar-star-duotone" /></template>
