<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nngs5gb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:attribution-outline-sharp" /></template>
<style>
.nngs5gb4q {
  fill: currentColor;
  d: path("M11.058 18.077h1.884v-4.116h1.308v-5h-4.5v5h1.308zm-2.555 2.216q-1.64-.708-2.864-1.932t-1.931-2.864T3 11.995t.71-3.5T5.64 5.64t2.862-1.93Q10.147 3 12.005 3t3.498.71t2.858 1.93t1.929 2.855q.71 1.637.71 3.5t-.71 3.505t-1.93 2.86t-2.855 1.93t-3.5.71t-3.502-.707m9.16-2.63Q20 15.325 20 12t-2.337-5.663T12 4T6.337 6.338T4 12t2.338 5.663T12 20t5.663-2.337M12.844 7.96q.348-.348.348-.844q0-.497-.348-.845T12 5.923t-.844.348t-.348.845t.348.844t.844.348t.844-.348M12 12");
}

</style>
