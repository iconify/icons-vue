<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt_7jqbdu.css';
import '../../css/b/b96vt-g1e.css';
import '../../css/l/l78zzhbem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dt_7jqbdu"/><path class="b96vt-g1e"/><path class="l78zzhbem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:leafwiki-light" /></template>
