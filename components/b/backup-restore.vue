<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/foc1nq.css';
import '../../css/s/s1ui7u.css';
import '../../css/l/ldiosp.css';
import '../../css/y/ydovum.css';
import '../../css/g/ggrt7r.css';
import '../../css/s/so-from-48.css';
import '../../css/f/fade-to-1.css';
import '../../css/d/d-k7l8fc.css';
import '../../css/r/r-to-0px.css';
import '../../css/r/r-to-2px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="foc1nq s1ui7u"/><path class="ldiosp s1ui7u ydovum"/><circle class="ggrt7r ydovum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:backup-restore" /></template>
