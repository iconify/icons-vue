<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px1zdkb_w.css';
import '../../css/c/cxwvkfgrp.css';
import '../../css/l/l4fo6w5ai.css';
import '../../css/n/nnyzwab4l.css';
import '../../css/l/lmf0ecbhq.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline--badged clr-i-outline-path-1--badged px1zdkb_w"/><path class="clr-i-outline--badged clr-i-outline-path-2--badged cxwvkfgrp"/><path class="clr-i-outline--badged clr-i-outline-path-3--badged l4fo6w5ai"/><path class="clr-i-outline--badged clr-i-outline-path-4--badged nnyzwab4l"/><circle class="clr-i-badge clr-i-outline--badged clr-i-outline-path-5--badged lmf0ecbhq"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:file-settings-outline-badged" /></template>
