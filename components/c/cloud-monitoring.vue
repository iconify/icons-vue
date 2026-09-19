<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8qb438it.css';
import '../../css/l/lhvcaet_c.css';
import '../../css/w/wu_w831hd.css';
import '../../css/t/txx4xebwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u8qb438it"/><path class="lhvcaet_c"/><path class="wu_w831hd"/><rect class="txx4xebwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:cloud-monitoring" /></template>
