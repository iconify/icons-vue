<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bg6kwf9gu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:earbuds-battery-outline" /></template>
<style>
.bg6kwf9gu {
  fill: currentColor;
  d: path("M18.577 7.346v-.769h1v.77h1.154q.328 0 .549.22q.22.22.22.549v8.615q0 .328-.22.549t-.55.22h-3.307q-.329 0-.549-.22t-.22-.55V8.117q0-.33.22-.55t.549-.22zm-.923 9.154H20.5zm-14.266.112q-.888-.889-.888-2.18V8.27q0-.71.491-1.2q.492-.492 1.201-.492t1.201.491t.492 1.201t-.492 1.201t-1.2.491q-.203 0-.414-.063q-.212-.063-.395-.19v4.725q0 .915.634 1.549t1.55.634t1.548-.634t.634-1.55V9.645q0-1.29.889-2.179q.888-.888 2.178-.888t2.18.879q.888.878.888 2.188v6.164q0 .71-.492 1.2q-.491.492-1.2.492q-.71 0-1.202-.491q-.491-.492-.491-1.201t.491-1.201t1.201-.492q.202 0 .414.064q.211.063.394.19V9.644q0-.915-.634-1.549q-.633-.634-1.549-.634t-1.549.634t-.633 1.55v4.788q0 1.29-.889 2.178q-.888.889-2.179.889t-2.178-.889m14.265-.111H20.5V8.346h-2.846z");
}

</style>
