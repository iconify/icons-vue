<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr7_wabhq.css';
import '../../css/r/r3nawdb_c.css';
import '../../css/c/c-wx2xbdp.css';
import '../../css/e/ejz18pb3u.css';
import '../../css/r/ro6p7mb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tr7_wabhq"/><path class="r3nawdb_c"/><path class="c-wx2xbdp"/><path class="ejz18pb3u"/><path class="ro6p7mb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:autonomous-car-20" /></template>
