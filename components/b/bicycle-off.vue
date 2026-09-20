<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="de1o0icpa"/><path clip-rule="evenodd" class="hzw-4zbaa"/><path class="eydaci5kk"/><path clip-rule="evenodd" class="trgw8wbho"/><path class="avpjygb2j"/><path class="xedf9ccsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:bicycle-off" /></template>
<style>
.avpjygb2j {
  d: path("m13.98 2.743l2.5 12.562c.261 1.308-1.7 1.698-1.96.39l-2.5-12.562c-.261-1.307 1.7-1.698 1.96-.39");
}

.cuyn6tgcc {
  fill: currentColor;
}

.de1o0icpa {
  d: path("M13.062 3.936a1 1 0 1 1-.124-1.996C16.828 1.7 19 2.46 19 4.44c0 1.574-.978 2.274-2.855 2.55a1 1 0 1 1-.29-1.98C16.87 4.862 17 4.77 17 4.44c0-.296-1.094-.68-3.938-.504");
}

.eydaci5kk {
  d: path("M5 6.5a1 1 0 0 1 0-2h4a1 1 0 0 1 0 2z");
}

.hzw-4zbaa {
  fill-rule: evenodd;
  d: path("M15.5 20a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9m0-7a2.5 2.5 0 1 1 0 5a2.5 2.5 0 0 1 0-5m-11 7a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9m0-7a2.5 2.5 0 1 1 0 5a2.5 2.5 0 0 1 0-5");
}

.trgw8wbho {
  fill-rule: evenodd;
  d: path("M4.5 16.5H10a1 1 0 0 0 .983-1.185l3.864-6.165A1 1 0 0 0 14 7.619H8.45l-.802-2.432a1 1 0 0 0-1.9.627L6.755 8.86l-3.146 6.186A1 1 0 0 0 4.5 16.5m3.138-4.964L6.13 14.5h2.487zm2.536 1.303l2.019-3.22H9.111z");
}

.xedf9ccsf {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
