<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6fx3-bru.css';
import '../../css/n/nb-eyybsf.css';
import '../../css/d/drz7i217o.css';
import '../../css/p/ppjdh5n8d.css';
import '../../css/b/bjta2obvc.css';
import '../../css/b/b73w8webg.css';
import '../../css/f/fiklt3b5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="k6fx3-bru"/><path class="nb-eyybsf"/><path class="drz7i217o"/><path class="ppjdh5n8d"/><path class="bjta2obvc"/><path class="b73w8webg"/><path class="fiklt3b5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-ui:eye" /></template>
