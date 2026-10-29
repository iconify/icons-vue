<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eyzyv9lqb.css';
import '../../css/p/pefcugrti.css';
import '../../css/l/lt1oixs7c.css';
import '../../css/c/c_tiat4ia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eyzyv9lqb wm-k"/><path class="pefcugrti wm-a"/><path class="lt1oixs7c wm-a"/><path class="c_tiat4ia wm-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:calculator" /></template>
