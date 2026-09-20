<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ryli0b21x.css';
import '../../css/k/kxrdghhzg.css';
import '../../css/v/vsuf1kbiw.css';
import '../../css/j/jn8qy4bru.css';
import '../../css/b/b40mtibns.css';
import '../../css/w/wok593inm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="ryli0b21x"/><circle class="kxrdghhzg"/><path class="vsuf1kbiw"/><g class="jn8qy4bru"><path class="b40mtibns"/><path class="wok593inm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:emergency-exit" /></template>
