<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/lpv9xrbna.css';
import '../../css/q/q8dnq5b2g.css';
import '../../css/y/y2b9f6bkz.css';
import '../../css/y/yt3gx6m5l.css';
import '../../css/a/a81qf0e1m.css';
import '../../css/f/f-0hfrben.css';
import '../../css/e/e2szqbc8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="lpv9xrbna wm-shadow"/><path class="q8dnq5b2g wm-k"/><path class="wm-k y2b9f6bkz"/><path class="wm-k yt3gx6m5l"/><path class="a81qf0e1m wm-a"/><path class="f-0hfrben wm-a"/><path class="e2szqbc8b wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-bunny-engrave" /></template>
