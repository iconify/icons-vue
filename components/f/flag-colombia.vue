<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dur0b2p3t.css';
import '../../css/l/lk8duns4e.css';
import '../../css/q/qh9qlceui.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="dur0b2p3t"/><path class="lk8duns4e"/><path class="qh9qlceui"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:flag-colombia" /></template>
