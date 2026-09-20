<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rn6cf5bmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chess-king-2" /></template>
<style>
.rn6cf5bmu {
  fill: currentColor;
  d: path("M12.5 21v-6.856q0-.558.172-1.099t.547-.968q.985-1.165 2.388-1.833t3.047-.667q1.38 0 2.363.973T22 12.923v4.73q0 1.382-.983 2.364T18.654 21zm-7.154 0q-1.38 0-2.363-.983T2 17.654v-4.731q0-1.4.983-2.373t2.363-.973q1.65 0 3.078.702t2.413 1.892q.35.408.506.912t.157 1.061V21zM12 11.933q-.671-.921-1.612-1.723T8.22 9.134q.696-.665 1.522-1.002t1.757-.405v-1.88H8.654v-1H11.5V2h1v2.846h2.846v1H12.5v1.875q.937.068 1.77.408q.832.34 1.528 1.006q-1.206.292-2.157 1.094q-.95.802-1.641 1.704");
}

</style>
