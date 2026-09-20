<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqax-6b-d.css';
import '../../css/r/rc6h4dq6f.css';
import '../../css/s/sjg59cb2m.css';
import '../../css/d/d-ekqwgrr.css';
import '../../css/q/qd4nuxbqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="jqax-6b-d"><path class="rc6h4dq6f"/><path class="sjg59cb2m"/><path class="d-ekqwgrr"/><path class="qd4nuxbqg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:burger" /></template>
