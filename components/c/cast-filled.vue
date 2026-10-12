<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sthnq_bas.css';
import '../../css/k/k0rk_ubdy.css';
import '../../css/l/ljyzvbntq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sthnq_bas"/><path class="k0rk_ubdy"/><path class="ljyzvbntq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:cast-filled" /></template>
