<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ui7xt3chp.css';
import '../../css/a/aqhy-8h6r.css';
import '../../css/i/i0rmnxk2w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ui7xt3chp"/><path class="aqhy-8h6r"/><path clip-rule="evenodd" class="i0rmnxk2w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bug-minimalistic-outline" /></template>
