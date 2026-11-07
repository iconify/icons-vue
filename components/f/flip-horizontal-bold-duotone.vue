<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xtpeb-edw.css';
import '../../css/p/pb9gzdd5r.css';
import '../../css/f/f8c-vr1fw.css';
import '../../css/b/bi-4r3b3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="xtpeb-edw"><path class="pb9gzdd5r"/><path class="f8c-vr1fw"/></g><path clip-rule="evenodd" class="bi-4r3b3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:flip-horizontal-bold-duotone" /></template>
