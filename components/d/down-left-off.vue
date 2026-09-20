<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/pr0chacef.css';
import '../../css/e/efper0b_o.css';
import '../../css/l/l87812muk.css';
import '../../css/j/je5vd7bsn.css';
import '../../css/i/i3s9_b4fi.css';
import '../../css/m/mo5netbri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><g clip-rule="evenodd" class="pr0chacef"><path class="efper0b_o"/><path class="l87812muk"/></g><path clip-rule="evenodd" class="je5vd7bsn"/><path clip-rule="evenodd" class="i3s9_b4fi"/><path class="mo5netbri"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:down-left-off" /></template>
