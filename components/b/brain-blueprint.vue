<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/l/lbvzj5boa.css';
import '../../css/t/tz579yb5k.css';
import '../../css/y/yek68-ben.css';
import '../../css/a/aba7yvbtg.css';
import '../../css/k/k352ru_jx.css';
import '../../css/k/k3qxsn1-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="lbvzj5boa wm-deco"/><path class="tz579yb5k wm-deco"/><path class="wm-deco yek68-ben"/><path class="aba7yvbtg wm-k"/><path class="k352ru_jx wm-a"/><path class="k3qxsn1-f wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:brain-blueprint" /></template>
