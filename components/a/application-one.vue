<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/l/lmoo01bav.css';
import '../../css/k/k5rx2ix5o.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGyZNfyd1N"><g class="ufeehvblu"><path class="lmoo01bav"/><path class="k5rx2ix5o"/></g></mask></defs><path mask="url(#SVGyZNfyd1N)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:application-one" /></template>
