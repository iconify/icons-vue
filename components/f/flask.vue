<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/b/bgqgxn_2a.css';
import '../../css/d/d9c6cujor.css';
import '../../css/y/yu50zccjs.css';
import '../../css/d/d3qbv9-rb.css';
import '../../css/o/oh5umcdmk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="bgqgxn_2a"/><path class="d9c6cujor"/><path class="yu50zccjs"/><circle class="d3qbv9-rb"/><circle class="oh5umcdmk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:flask" /></template>
