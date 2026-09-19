<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/l/lvwaq0byj.css';
import '../../css/j/jc5ieqbjf.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGhvLPJbvx"><g class="ufeehvblu"><path class="lvwaq0byj"/><path class="jc5ieqbjf"/></g></mask></defs><path mask="url(#SVGhvLPJbvx)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:exchange-three" /></template>
