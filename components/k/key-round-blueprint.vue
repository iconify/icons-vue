<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/n/nqm7mkz3u.css';
import '../../css/k/k63y7j0zf.css';
import '../../css/g/goo9dshtt.css';
import '../../css/t/tvug85bii.css';
import '../../css/i/ibqsyxb2r.css';
import '../../css/b/b86m5ybhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="nqm7mkz3u wm-deco"/><path class="k63y7j0zf wm-deco"/><path class="goo9dshtt wm-deco"/><path class="tvug85bii wm-k"/><path class="ibqsyxb2r wm-a"/><path class="b86m5ybhz wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:key-round-blueprint" /></template>
