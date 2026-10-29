<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/o/oiy2qljci.css';
import '../../css/o/ovlj1tyub.css';
import '../../css/n/nge5cfbll.css';
import '../../css/k/krslsibqq.css';
import '../../css/i/ib2mi1bmy.css';
import '../../css/p/pce7ldb7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="oiy2qljci wm-deco"/><path class="ovlj1tyub wm-deco"/><path class="nge5cfbll wm-deco"/><path class="krslsibqq wm-k"/><path class="ib2mi1bmy wm-a"/><path class="pce7ldb7f wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chocolate-box-blueprint" /></template>
