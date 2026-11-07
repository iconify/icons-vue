<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzudi5blo.css';
import '../../css/s/snglypb8l.css';
import '../../css/e/e---ckffe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zzudi5blo"/><path class="snglypb8l"/><path clip-rule="evenodd" class="e---ckffe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gallery-circle-bold-duotone" /></template>
