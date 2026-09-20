<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wilx9023w.css';
import '../../css/d/dn6s-ubtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wilx9023w"/><path class="dn6s-ubtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:dependabot-24" /></template>
