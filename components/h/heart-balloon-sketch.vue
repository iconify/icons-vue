<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/fio839f8b.css';
import '../../css/t/t0ylnq39z.css';
import '../../css/i/izxst9d8w.css';
import '../../css/g/govvadqsn.css';
import '../../css/t/tt0w_4bls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="fio839f8b"/><path class="t0ylnq39z wm-k"/><path class="izxst9d8w wm-a"/><path class="govvadqsn wm-k"/><path class="tt0w_4bls wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:heart-balloon-sketch" /></template>
