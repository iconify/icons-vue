<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fx73xpb2j.css';
import '../../css/i/i-yovpx2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fx73xpb2j"/><path class="i-yovpx2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:key-asterisk-24" /></template>
