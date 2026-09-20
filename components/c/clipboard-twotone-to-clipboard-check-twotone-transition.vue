<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c92a3r.css';
import '../../css/q/qa-o7h.css';
import '../../css/t/taf2xz.css';
import '../../css/w/wc7n7b.css';
import '../../css/e/ecu16w.css';
import '../../css/b/b1659c.css';
import '../../css/s/so-from-12.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c92a3r"/><path class="qa-o7h taf2xz wc7n7b"/><path class="ecu16w qa-o7h"/><path class="b1659c qa-o7h taf2xz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:clipboard-twotone-to-clipboard-check-twotone-transition" /></template>
