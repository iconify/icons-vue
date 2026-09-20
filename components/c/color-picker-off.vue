<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ga2me1xwp"/><path class="kcdthlb9a"/><path class="b83vi8tez"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:color-picker-off" /></template>
<style>
.b83vi8tez {
  d: path("M14.39 4.14a1 1 0 1 1-1.415-1.414a3 3 0 1 1 4.243 4.243a1 1 0 1 1-1.415-1.414A1 1 0 0 0 14.39 4.14m-4.953.705a1 1 0 0 1 1.415-1.414l5.656 5.657a1 1 0 0 1-1.414 1.414zM1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ga2me1xwp {
  fill-rule: evenodd;
  d: path("M7.536 15.237c-1.56.616-4.257 2.37-4.728 1.9c-.306-.306.323-1.546.972-2.806h4.66z");
}

.kcdthlb9a {
  d: path("M15.803 5.555a1 1 0 1 1 1.415 1.414l-8.975 8.975a1 1 0 0 1-.34.222c-.396.157-.8.355-1.753.846c-.47.242-.679.348-.933.474c-1.748.861-2.405 1.068-3.116.357c-.71-.71-.504-1.367.351-3.105c.127-.257.234-.468.48-.945c.491-.953.689-1.356.845-1.753A1 1 0 0 1 4 11.701l8.975-8.975a1 1 0 1 1 1.414 1.414l-8.832 8.833c-.174.414-.393.855-.847 1.736a52 52 0 0 0-.535 1.06l.158-.077c.24-.119.441-.221.902-.458c.88-.454 1.321-.673 1.736-.847z");
}

</style>
