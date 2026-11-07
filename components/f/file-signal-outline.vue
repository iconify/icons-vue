<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kp4tifbel.css';
import '../../css/b/bdbim4bgo.css';
import '../../css/t/tl0l83b8e.css';
import '../../css/d/d25mwn3tm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kp4tifbel"/><path class="bdbim4bgo"/><path clip-rule="evenodd" class="tl0l83b8e"/><path clip-rule="evenodd" class="d25mwn3tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-signal-outline" /></template>
