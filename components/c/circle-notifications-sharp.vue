<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dno1akgbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:circle-notifications-sharp" /></template>
<style>
.dno1akgbn {
  fill: currentColor;
  d: path("M12.851 17.543q.36-.341.418-.85h-2.538q.058.509.418.85t.851.341t.851-.34m-5.082-2.39h8.462v-1.231h-1v-2.715q0-1.275-.672-2.317q-.672-1.041-1.867-1.314V6.039h-1.384v1.538q-1.195.273-1.867 1.295t-.672 2.297v2.754h-1zM12.003 21q-1.866 0-3.51-.708q-1.643-.709-2.859-1.924t-1.925-2.856T3 12.003t.709-3.51Q4.417 6.85 5.63 5.634t2.857-1.925T11.997 3t3.51.709q1.643.708 2.859 1.922t1.925 2.857t.709 3.509t-.708 3.51t-1.924 2.859t-2.856 1.925t-3.509.709");
}

</style>
