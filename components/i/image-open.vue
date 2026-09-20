<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ens04999i.css';
import '../../css/n/n_xfstkmc.css';
import '../../css/h/h03pgbcln.css';
import '../../css/m/mntmc0b2z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ens04999i"/><path class="n_xfstkmc"/><path class="h03pgbcln"/><path class="mntmc0b2z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:image-open" /></template>
